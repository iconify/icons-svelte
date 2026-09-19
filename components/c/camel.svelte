<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbk1cv1_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbk1cv1_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:camel" {...props}></Icon>
