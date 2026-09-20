<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrtt16bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yrtt16bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mobile-signal-one-solid" {...props}></Icon>
