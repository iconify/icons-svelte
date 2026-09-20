<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb1rlrvlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jb1rlrvlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:cloud-check-solid" {...props}></Icon>
