<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/van_eiakz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="van_eiakz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:config-vertical-solid" {...props}></Icon>
