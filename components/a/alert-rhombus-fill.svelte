<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/baly-1ssn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="baly-1ssn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alert-rhombus-fill" {...props}></Icon>
