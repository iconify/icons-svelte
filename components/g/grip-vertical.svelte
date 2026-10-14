<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnfl3zb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mnfl3zb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:grip-vertical" {...props}></Icon>
