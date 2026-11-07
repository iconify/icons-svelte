<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwn8jibaq.css';
import '../../css/t/tksc1h7ms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwn8jibaq"/><path class="tksc1h7ms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:eraser-bold" {...props}></Icon>
