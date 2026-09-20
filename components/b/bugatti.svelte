<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa-hsbc_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa-hsbc_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bugatti" {...props}></Icon>
