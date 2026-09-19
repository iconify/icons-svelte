<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlznznb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlznznb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:circle-half-filled" {...props}></Icon>
