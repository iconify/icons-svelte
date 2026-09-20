<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnqvqz_ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnqvqz_ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:eraser-sharp" {...props}></Icon>
