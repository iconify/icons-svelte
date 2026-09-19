<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga4ciopbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga4ciopbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:php-fill" {...props}></Icon>
