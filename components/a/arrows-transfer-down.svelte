<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/va7509xco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="va7509xco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-transfer-down" {...props}></Icon>
