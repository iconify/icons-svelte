<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8vd62j-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8vd62j-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:broccoli-filled" {...props}></Icon>
