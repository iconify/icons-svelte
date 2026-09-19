<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q56ww9qjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q56ww9qjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:diameter-solid" {...props}></Icon>
