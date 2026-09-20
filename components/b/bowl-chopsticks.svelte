<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj3j_obax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj3j_obax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bowl-chopsticks" {...props}></Icon>
