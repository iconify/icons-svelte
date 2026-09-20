<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaxf6993j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jaxf6993j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pavilion-fill" {...props}></Icon>
