<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmm6tlmsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nmm6tlmsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:magicmirror2-light" {...props}></Icon>
