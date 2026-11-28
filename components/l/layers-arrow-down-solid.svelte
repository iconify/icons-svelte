<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdze-ty3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qdze-ty3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:layers-arrow-down-solid" {...props}></Icon>
