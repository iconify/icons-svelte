<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t33jnj4eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t33jnj4eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:lock-alt" {...props}></Icon>
