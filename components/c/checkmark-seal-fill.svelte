<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi1la0bde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xi1la0bde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:checkmark-seal-fill" {...props}></Icon>
