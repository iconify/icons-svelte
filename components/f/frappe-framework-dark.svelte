<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcn4mte4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hcn4mte4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-framework-dark" {...props}></Icon>
