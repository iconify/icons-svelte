<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm301m7yg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mm301m7yg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:fridge-filled" {...props}></Icon>
