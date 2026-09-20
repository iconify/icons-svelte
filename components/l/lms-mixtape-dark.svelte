<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf5ej1owf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qf5ej1owf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lms-mixtape-dark" {...props}></Icon>
