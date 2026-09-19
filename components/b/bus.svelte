<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czum-8bsq.css';
import '../../css/v/vk88lsh0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czum-8bsq duoicon-secondary-layer"/><path class="duoicon-primary-layer vk88lsh0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:bus" {...props}></Icon>
