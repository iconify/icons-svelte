<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gne2u-3fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gne2u-3fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-packer-light" {...props}></Icon>
