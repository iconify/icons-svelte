<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0eark_fr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q0eark_fr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:medical" {...props}></Icon>
