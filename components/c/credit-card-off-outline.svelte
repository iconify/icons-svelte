<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvtoirlxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvtoirlxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-off-outline" {...props}></Icon>
