<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_yp45bso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o_yp45bso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hips" {...props}></Icon>
