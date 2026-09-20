<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgy4qqb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgy4qqb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-bar-up" {...props}></Icon>
