<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egs57ly1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="egs57ly1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:customize" {...props}></Icon>
