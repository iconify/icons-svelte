<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7pm8bbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="s7pm8bbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:periscope" {...props}></Icon>
