<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_sjz8b4l.css';
import '../../css/c/c080srerl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_sjz8b4l"/><path class="c080srerl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:html5" {...props}></Icon>
