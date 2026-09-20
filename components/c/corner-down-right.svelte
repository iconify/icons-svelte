<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfxgjg_6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jfxgjg_6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-down-right" {...props}></Icon>
