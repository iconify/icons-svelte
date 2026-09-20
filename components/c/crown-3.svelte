<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjp33xwpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tjp33xwpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:crown-3" {...props}></Icon>
