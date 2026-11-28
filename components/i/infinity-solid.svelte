<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/capct4svl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="capct4svl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:infinity-solid" {...props}></Icon>
