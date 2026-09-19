<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6ig82bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6ig82bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:comment-add" {...props}></Icon>
