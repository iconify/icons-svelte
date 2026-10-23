<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iba52wwer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iba52wwer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:credit-card-check" {...props}></Icon>
