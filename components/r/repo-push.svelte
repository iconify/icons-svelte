<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkv1f1b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="tkv1f1b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:repo-push" {...props}></Icon>
