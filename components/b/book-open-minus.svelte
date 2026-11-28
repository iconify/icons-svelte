<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ersqvpmuj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ersqvpmuj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:book-open-minus" {...props}></Icon>
