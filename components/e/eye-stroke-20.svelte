<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob_63mboo.css';
import '../../css/w/w55hdcgdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ob_63mboo"/><path class="w55hdcgdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:eye-stroke-20" {...props}></Icon>
