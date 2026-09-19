<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wro861b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wro861b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:laptop-windows-alt" {...props}></Icon>
