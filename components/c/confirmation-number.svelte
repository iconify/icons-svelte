<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a84a1jczv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="a84a1jczv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:confirmation-number" {...props}></Icon>
