<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4nfcllrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4nfcllrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:chevron-left-right-solid" {...props}></Icon>
