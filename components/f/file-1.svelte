<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvivz2ben.css';
import '../../css/z/zznnyf-1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":24};
const content = `<path class="cvivz2ben"/><path class="zznnyf-1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:file-1" {...props}></Icon>
