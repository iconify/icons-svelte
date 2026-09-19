<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im5rk1brm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im5rk1brm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:data" {...props}></Icon>
