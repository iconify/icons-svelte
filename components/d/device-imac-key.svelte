<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adv3nryks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="adv3nryks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-key" {...props}></Icon>
