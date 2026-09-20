<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn9d9bbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn9d9bbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:code" {...props}></Icon>
