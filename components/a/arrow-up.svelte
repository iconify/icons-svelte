<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo1wz-2dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo1wz-2dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-up" {...props}></Icon>
