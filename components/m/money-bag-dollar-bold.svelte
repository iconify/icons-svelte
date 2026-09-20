<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3ay99b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3ay99b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:money-bag-dollar-bold" {...props}></Icon>
