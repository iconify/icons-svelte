<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9xxyrxxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c9xxyrxxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:fit-height-solid" {...props}></Icon>
