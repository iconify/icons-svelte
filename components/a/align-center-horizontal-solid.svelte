<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmkk7pd3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gmkk7pd3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-center-horizontal-solid" {...props}></Icon>
