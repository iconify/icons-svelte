<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu-hfdcgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="mu-hfdcgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:download-circle-fill" {...props}></Icon>
