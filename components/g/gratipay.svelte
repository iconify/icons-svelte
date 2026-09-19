<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3gvyi5tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="b3gvyi5tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:gratipay" {...props}></Icon>
