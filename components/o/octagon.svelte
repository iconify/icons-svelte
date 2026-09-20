<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe5r8nmyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe5r8nmyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:octagon" {...props}></Icon>
