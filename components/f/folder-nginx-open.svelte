<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo_p2j3uc.css';
import '../../css/y/yorsrhfgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lo_p2j3uc"/><path class="yorsrhfgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-nginx-open" {...props}></Icon>
