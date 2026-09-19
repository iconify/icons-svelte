<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awq8skfug.css';
import '../../css/o/o-u5nubvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="awq8skfug"/><path class="o-u5nubvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:circle-up" {...props}></Icon>
