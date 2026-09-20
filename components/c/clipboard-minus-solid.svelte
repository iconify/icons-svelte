<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_ghkibrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="y_ghkibrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:clipboard-minus-solid" {...props}></Icon>
