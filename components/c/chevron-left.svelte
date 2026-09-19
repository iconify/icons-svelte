<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v12-rwbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":160,"height":384};
const content = `<path class="v12-rwbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:chevron-left" {...props}></Icon>
