<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii1_3rbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii1_3rbrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:quote-outline" {...props}></Icon>
