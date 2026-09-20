<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp7d7ipnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp7d7ipnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-log-outline" {...props}></Icon>
