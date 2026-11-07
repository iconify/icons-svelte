<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz2ub5bko.css';
import '../../css/h/hazygbbpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vz2ub5bko"/><path class="hazygbbpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-with-files-bold" {...props}></Icon>
