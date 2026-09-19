<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6y5k5ocf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6y5k5ocf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cheque-thin" {...props}></Icon>
