<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m74ql-csp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="m74ql-csp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:arrow-circle-up-left" {...props}></Icon>
