<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rld69poao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rld69poao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:json-alt-1-fill" {...props}></Icon>
