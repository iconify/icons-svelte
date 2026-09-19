<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v88_xacul.css';
import '../../css/w/wtmn1wb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v88_xacul"/><path class="wtmn1wb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:info-circle" {...props}></Icon>
