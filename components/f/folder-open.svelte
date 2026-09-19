<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um_pv-brv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um_pv-brv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:folder-open" {...props}></Icon>
