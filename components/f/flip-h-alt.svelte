<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8-ajz3mr.css';
import '../../css/c/cw9ts4b7s.css';
import '../../css/l/lv8kz-w7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r8-ajz3mr"/><path class="cw9ts4b7s"/><path class="lv8kz-w7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:flip-h-alt" {...props}></Icon>
