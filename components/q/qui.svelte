<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mabrn8b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mabrn8b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:qui" {...props}></Icon>
