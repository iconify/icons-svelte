<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgfplbbgp.css';
import '../../css/g/gsi1lc1zm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kgfplbbgp"/><path class="gsi1lc1zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:edubuntu" {...props}></Icon>
