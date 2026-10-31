<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmoot56zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmoot56zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-uturn-up-left-solid" {...props}></Icon>
