<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vly9au3wd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="vly9au3wd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-26" {...props}></Icon>
