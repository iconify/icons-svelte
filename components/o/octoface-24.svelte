<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0hmkxdku.css';
import '../../css/x/x3768wg5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0hmkxdku"/><path class="x3768wg5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:octoface-24" {...props}></Icon>
