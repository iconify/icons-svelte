<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibo_w4bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibo_w4bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:radio-solid" {...props}></Icon>
