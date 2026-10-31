<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1n2jnbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f1n2jnbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-left-large-round" {...props}></Icon>
