<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwft6v2va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-2};
const content = `<path class="zwft6v2va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:pin-alt" {...props}></Icon>
