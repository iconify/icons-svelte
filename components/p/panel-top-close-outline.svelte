<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkaaq9b7k.css';
import '../../css/c/cre3c4s6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hkaaq9b7k"/><path clip-rule="evenodd" class="cre3c4s6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-top-close-outline" {...props}></Icon>
