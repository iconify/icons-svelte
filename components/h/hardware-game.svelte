<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnru82rqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnru82rqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:hardware-game" {...props}></Icon>
