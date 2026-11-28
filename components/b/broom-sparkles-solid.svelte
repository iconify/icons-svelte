<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez8p2nbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez8p2nbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:broom-sparkles-solid" {...props}></Icon>
