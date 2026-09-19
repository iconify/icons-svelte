<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1eird_2e.css';
import '../../css/u/uu2dy8rgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1eird_2e"/><path class="uu2dy8rgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dice-roll" {...props}></Icon>
