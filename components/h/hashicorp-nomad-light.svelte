<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a98mxbbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a98mxbbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hashicorp-nomad-light" {...props}></Icon>
