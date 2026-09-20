<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swgxpjn_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="swgxpjn_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:loading" {...props}></Icon>
