<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs_n-lber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs_n-lber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-uturn-down-right-solid" {...props}></Icon>
