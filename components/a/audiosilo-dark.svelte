<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgjzri7en.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kgjzri7en"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audiosilo-dark" {...props}></Icon>
