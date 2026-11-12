<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk0l0vvyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tk0l0vvyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-cloud-light" {...props}></Icon>
