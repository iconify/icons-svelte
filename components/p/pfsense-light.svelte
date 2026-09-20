<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tox88-zbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tox88-zbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pfsense-light" {...props}></Icon>
