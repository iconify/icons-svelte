<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aichv3_pv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aichv3_pv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:folder-alert" {...props}></Icon>
