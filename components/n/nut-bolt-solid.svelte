<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msigw46qa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msigw46qa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:nut-bolt-solid" {...props}></Icon>
