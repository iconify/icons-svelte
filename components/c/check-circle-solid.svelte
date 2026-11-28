<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t__uj6bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t__uj6bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:check-circle-solid" {...props}></Icon>
