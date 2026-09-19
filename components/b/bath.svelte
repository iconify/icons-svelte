<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7u-q6bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7u-q6bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:bath" {...props}></Icon>
