<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po7-grb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="po7-grb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:bank" {...props}></Icon>
