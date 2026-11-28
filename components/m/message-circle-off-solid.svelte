<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5g77ml3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5g77ml3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-off-solid" {...props}></Icon>
