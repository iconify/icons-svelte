<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5vq-i_qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h5vq-i_qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:heart" {...props}></Icon>
