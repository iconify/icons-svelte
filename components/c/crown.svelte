<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt5iptwmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mt5iptwmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:crown" {...props}></Icon>
