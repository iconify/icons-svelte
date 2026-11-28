<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvkvv28pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cvkvv28pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pear-solid" {...props}></Icon>
