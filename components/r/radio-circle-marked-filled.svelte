<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/doumpmbck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="doumpmbck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:radio-circle-marked-filled" {...props}></Icon>
