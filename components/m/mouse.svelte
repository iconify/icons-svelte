<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xk-i8_1pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":705,"height":1024};
const content = `<path class="xk-i8_1pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mouse" {...props}></Icon>
