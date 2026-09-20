<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es8-o6bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="es8-o6bof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-squatting-and-person-reaching-up" {...props}></Icon>
