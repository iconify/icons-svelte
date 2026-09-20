<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vm7abtb6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vm7abtb6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mydrive-light" {...props}></Icon>
