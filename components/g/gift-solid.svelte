<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5y0mrhjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5y0mrhjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:gift-solid" {...props}></Icon>
