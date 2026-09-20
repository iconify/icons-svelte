<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw-s8tbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pw-s8tbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:bluetooth" {...props}></Icon>
