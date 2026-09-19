<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv8_vibzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sv8_vibzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:play" {...props}></Icon>
