<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrvspvbct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrvspvbct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bank-remove" {...props}></Icon>
