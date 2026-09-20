<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k889x9ems.css';
import '../../css/y/ye4h3ob-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k889x9ems"/><path class="ye4h3ob-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:badge-verified-duotone" {...props}></Icon>
