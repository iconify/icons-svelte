<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx-8-ebcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qx-8-ebcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:person-fill" {...props}></Icon>
