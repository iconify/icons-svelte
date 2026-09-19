<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkfik5lax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="mkfik5lax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrowtriangle-up-fill" {...props}></Icon>
