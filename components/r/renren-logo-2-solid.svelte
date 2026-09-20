<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h14fegbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h14fegbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:renren-logo-2-solid" {...props}></Icon>
