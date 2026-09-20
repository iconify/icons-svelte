<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xlnerbb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xlnerbb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:boxing-glove-2" {...props}></Icon>
