<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1h5tybaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1h5tybaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:monorail-solid" {...props}></Icon>
