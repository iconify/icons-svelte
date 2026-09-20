<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm9g3ydmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zm9g3ydmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:accessibility-inset-24" {...props}></Icon>
