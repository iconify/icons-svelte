<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc1oq6b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oc1oq6b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:info-circle-solid" {...props}></Icon>
