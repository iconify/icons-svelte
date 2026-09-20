<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldnl1xm9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ldnl1xm9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:end-point-circle-bold" {...props}></Icon>
