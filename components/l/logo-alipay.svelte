<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulxc67bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ulxc67bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:logo-alipay" {...props}></Icon>
