<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6on6gbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="z6on6gbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-inner-solid" {...props}></Icon>
