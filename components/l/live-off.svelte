<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md_3dldtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md_3dldtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:live-off" {...props}></Icon>
