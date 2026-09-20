<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqj-v0bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mqj-v0bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kopia-dark" {...props}></Icon>
