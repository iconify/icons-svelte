<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewe_q1bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewe_q1bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-card" {...props}></Icon>
