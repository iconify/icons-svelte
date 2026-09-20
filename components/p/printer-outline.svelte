<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w01r25bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w01r25bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-outline" {...props}></Icon>
