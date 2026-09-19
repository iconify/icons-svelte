<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk3rzjcjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nk3rzjcjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:arrow-ios-forward-fill" {...props}></Icon>
