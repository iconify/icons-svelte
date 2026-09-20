<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib276704k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ib276704k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:phone-solid" {...props}></Icon>
