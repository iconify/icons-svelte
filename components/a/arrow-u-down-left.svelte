<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olsel1bem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="olsel1bem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-u-down-left" {...props}></Icon>
