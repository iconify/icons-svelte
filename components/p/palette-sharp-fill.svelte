<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/estk-xb6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="estk-xb6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:palette-sharp-fill" {...props}></Icon>
