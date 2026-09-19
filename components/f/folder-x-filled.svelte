<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g03z_wayl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g03z_wayl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:folder-x-filled" {...props}></Icon>
