<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnl_elb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cnl_elb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:hill-avalanche" {...props}></Icon>
