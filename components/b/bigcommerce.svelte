<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxh3hib-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxh3hib-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:bigcommerce" {...props}></Icon>
