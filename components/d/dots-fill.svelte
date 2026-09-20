<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz7on2bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz7on2bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dots-fill" {...props}></Icon>
