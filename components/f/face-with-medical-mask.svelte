<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9zkttbmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s9zkttbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:face-with-medical-mask" {...props}></Icon>
