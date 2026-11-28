<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh4xotmes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh4xotmes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:cloud-alert-solid" {...props}></Icon>
