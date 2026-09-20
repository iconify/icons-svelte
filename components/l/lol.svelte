<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn_zqnbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="sn_zqnbic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:lol" {...props}></Icon>
