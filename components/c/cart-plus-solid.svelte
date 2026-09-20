<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqqz5kbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cqqz5kbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:cart-plus-solid" {...props}></Icon>
