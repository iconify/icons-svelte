<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvg_1-o8n.css';
import '../../css/m/m0esjaiqj.css';
import '../../css/a/abtzwvxwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="uvg_1-o8n"/><rect class="m0esjaiqj"/><path class="abtzwvxwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-horizontal-justify-center-filled" {...props}></Icon>
