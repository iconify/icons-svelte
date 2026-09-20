<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngd1m3bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngd1m3bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:currency-uah" {...props}></Icon>
