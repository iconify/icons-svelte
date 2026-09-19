<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n49mtlg2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n49mtlg2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gender-female" {...props}></Icon>
