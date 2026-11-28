<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxsh7ebsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxsh7ebsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:edit-solid" {...props}></Icon>
