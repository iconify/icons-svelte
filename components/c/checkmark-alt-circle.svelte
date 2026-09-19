<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crld5ikee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="crld5ikee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:checkmark-alt-circle" {...props}></Icon>
