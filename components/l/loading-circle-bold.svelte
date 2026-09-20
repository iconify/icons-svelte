<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxvktzhsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxvktzhsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:loading-circle-bold" {...props}></Icon>
