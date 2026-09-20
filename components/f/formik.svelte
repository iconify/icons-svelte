<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-a8pibti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-a8pibti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:formik" {...props}></Icon>
