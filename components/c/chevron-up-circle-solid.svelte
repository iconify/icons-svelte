<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkm_1v9vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkm_1v9vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chevron-up-circle-solid" {...props}></Icon>
