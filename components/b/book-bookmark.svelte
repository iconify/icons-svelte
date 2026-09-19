<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mps24piji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mps24piji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:book-bookmark" {...props}></Icon>
