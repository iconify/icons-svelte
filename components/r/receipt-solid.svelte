<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce4r_lgpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ce4r_lgpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:receipt-solid" {...props}></Icon>
