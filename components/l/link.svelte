<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvgjsjngl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvgjsjngl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:link" {...props}></Icon>
