<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrth6ob1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-1.5};
const content = `<path class="yrth6ob1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:pin-alt-f" {...props}></Icon>
