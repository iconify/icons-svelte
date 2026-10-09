<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky693gb4a.css';
import '../../css/m/mkb2ul-2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ky693gb4a"/><path class="mkb2ul-2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hex-nut-20" {...props}></Icon>
