<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m950ohb-k.css';
import '../../css/z/z1vhpmnls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m950ohb-k"/><circle class="z1vhpmnls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:docker-volume-backup" {...props}></Icon>
