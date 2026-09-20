<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzxu6cbem.css';
import '../../css/l/l5bgdtbpm.css';
import '../../css/t/t9nocfb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gzxu6cbem"/><path class="l5bgdtbpm"/><path class="t9nocfb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-onedrive-dark" {...props}></Icon>
