<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jyi_wcczr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jyi_wcczr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:flame-off-filled" {...props}></Icon>
