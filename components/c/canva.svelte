<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqi20zl9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqi20zl9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:canva" {...props}></Icon>
