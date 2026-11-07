<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akziae8mx.css';
import '../../css/h/h3ccn7bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akziae8mx"/><path class="h3ccn7bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-bolt-bold" {...props}></Icon>
