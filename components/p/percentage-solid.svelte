<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4xqo48ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o4xqo48ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:percentage-solid" {...props}></Icon>
