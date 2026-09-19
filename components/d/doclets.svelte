<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ua6_9pbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ua6_9pbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:doclets" {...props}></Icon>
