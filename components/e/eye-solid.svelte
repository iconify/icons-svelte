<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpydcqtcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpydcqtcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:eye-solid" {...props}></Icon>
