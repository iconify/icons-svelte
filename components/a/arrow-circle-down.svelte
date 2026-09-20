<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldtu0gu7y.css';
import '../../css/t/tdnjtvgqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldtu0gu7y"/><path class="tdnjtvgqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:arrow-circle-down" {...props}></Icon>
