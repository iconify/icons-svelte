<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t02emlbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t02emlbpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-bold" {...props}></Icon>
