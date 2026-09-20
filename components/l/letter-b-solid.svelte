<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_isx3wzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_isx3wzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-b-solid" {...props}></Icon>
