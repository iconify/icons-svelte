<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjvrz1t5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjvrz1t5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:panel-right-inactive-solid" {...props}></Icon>
