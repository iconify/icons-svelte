<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iap_x96bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iap_x96bz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:dessert" {...props}></Icon>
