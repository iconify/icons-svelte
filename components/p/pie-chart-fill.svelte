<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd0bgsbjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wd0bgsbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pie-chart-fill" {...props}></Icon>
