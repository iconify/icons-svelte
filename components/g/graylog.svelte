<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uju6rdxwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uju6rdxwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:graylog" {...props}></Icon>
