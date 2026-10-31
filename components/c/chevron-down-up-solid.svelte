<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-i77zbsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-i77zbsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-down-up-solid" {...props}></Icon>
