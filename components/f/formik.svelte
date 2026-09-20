<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_70_7k6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_70_7k6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:formik" {...props}></Icon>
