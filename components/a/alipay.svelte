<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx1b4ebgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dx1b4ebgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:alipay" {...props}></Icon>
