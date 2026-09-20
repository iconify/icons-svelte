<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vecmprbqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vecmprbqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chart-no-axes-combined-fill" {...props}></Icon>
