<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzbwtpvzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzbwtpvzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-33-small" {...props}></Icon>
