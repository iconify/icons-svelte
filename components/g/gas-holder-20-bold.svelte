<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soauwjbuz.css';
import '../../css/x/xqe1shbes.css';
import '../../css/w/wp_1hutrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="soauwjbuz"/><path class="xqe1shbes"/><path class="wp_1hutrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-holder-20-bold" {...props}></Icon>
