<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l42_9wqpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l42_9wqpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:chevron-double-right-outline" {...props}></Icon>
