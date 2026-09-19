<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htlnq8bmb.css';
import '../../css/o/oeu2lyeho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htlnq8bmb"/><path class="oeu2lyeho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-left-stroke-circle-half-filled" {...props}></Icon>
