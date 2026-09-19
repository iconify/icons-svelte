<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw1k4kbnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="iw1k4kbnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:percent-badge-16-solid" {...props}></Icon>
