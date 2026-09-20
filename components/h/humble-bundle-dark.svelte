<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avw7e7kpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="avw7e7kpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:humble-bundle-dark" {...props}></Icon>
