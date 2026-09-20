<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8y38_bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m8y38_bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-center-vertical-outline" {...props}></Icon>
