<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqw06qb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cqw06qb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:area-chart-alt-outline" {...props}></Icon>
