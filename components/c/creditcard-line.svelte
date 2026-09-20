<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur1minbwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur1minbwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:creditcard-line" {...props}></Icon>
