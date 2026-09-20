<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dko7bgbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dko7bgbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:padlock-square-1-solid" {...props}></Icon>
