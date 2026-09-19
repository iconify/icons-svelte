<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/paxaq7ccy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="paxaq7ccy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:minus-shield-filled" {...props}></Icon>
