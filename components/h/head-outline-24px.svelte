<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guxx7ccxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="guxx7ccxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:head-outline-24px" {...props}></Icon>
