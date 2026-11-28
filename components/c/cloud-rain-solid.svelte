<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty7jkabah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty7jkabah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-rain-solid" {...props}></Icon>
