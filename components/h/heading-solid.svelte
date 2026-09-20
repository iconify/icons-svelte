<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p61rgibvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p61rgibvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:heading-solid" {...props}></Icon>
