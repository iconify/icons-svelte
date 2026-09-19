<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4646pbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4646pbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:auto-conversations" {...props}></Icon>
