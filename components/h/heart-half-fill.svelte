<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnqvoybla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnqvoybla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heart-half-fill" {...props}></Icon>
