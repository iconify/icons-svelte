<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q706zcc7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q706zcc7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:chevron-left" {...props}></Icon>
