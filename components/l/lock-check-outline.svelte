<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/os-g09bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="os-g09bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lock-check-outline" {...props}></Icon>
