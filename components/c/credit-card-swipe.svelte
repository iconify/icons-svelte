<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-n6ud5vm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-n6ud5vm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:credit-card-swipe" {...props}></Icon>
