<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x26-eabit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x26-eabit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:button-move-circle-solid" {...props}></Icon>
