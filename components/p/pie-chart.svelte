<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3zl73i7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k3zl73i7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:pie-chart" {...props}></Icon>
