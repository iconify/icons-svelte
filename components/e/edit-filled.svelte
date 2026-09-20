<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waq7ozb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waq7ozb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:edit-filled" {...props}></Icon>
