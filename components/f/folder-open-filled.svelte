<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmb_z30dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmb_z30dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:folder-open-filled" {...props}></Icon>
