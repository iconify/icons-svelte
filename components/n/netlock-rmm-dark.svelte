<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng0t87pbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ng0t87pbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netlock-rmm-dark" {...props}></Icon>
