<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okfctab9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":384};
const content = `<path class="okfctab9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:arrow-left-bottom" {...props}></Icon>
