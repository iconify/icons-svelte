<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9hz5nq9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t9hz5nq9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pi-alert-dark" {...props}></Icon>
