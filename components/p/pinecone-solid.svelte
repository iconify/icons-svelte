<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf4jwv82w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kf4jwv82w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pinecone-solid" {...props}></Icon>
