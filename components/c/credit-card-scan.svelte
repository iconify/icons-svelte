<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k12xm9bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k12xm9bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-scan" {...props}></Icon>
