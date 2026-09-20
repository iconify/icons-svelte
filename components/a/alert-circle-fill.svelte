<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awleaubuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="awleaubuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alert-circle-fill" {...props}></Icon>
