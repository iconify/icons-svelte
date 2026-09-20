<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnym_lbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hnym_lbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:credit-card-off" {...props}></Icon>
