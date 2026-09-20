<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m46eym3cb.css';
import '../../css/i/i-yovpx2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m46eym3cb"/><path class="i-yovpx2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:diff-renamed-24" {...props}></Icon>
