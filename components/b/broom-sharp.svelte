<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnyd66bmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnyd66bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:broom-sharp" {...props}></Icon>
