<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr52k_9za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cr52k_9za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-check-solid" {...props}></Icon>
