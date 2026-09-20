<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddd5e-bkc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddd5e-bkc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:pentagon-remix" {...props}></Icon>
