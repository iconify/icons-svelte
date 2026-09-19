<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej1okobup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ej1okobup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:border-none" {...props}></Icon>
