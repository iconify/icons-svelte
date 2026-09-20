<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_12uccoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e_12uccoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-bicycle-down-uneven-slope" {...props}></Icon>
