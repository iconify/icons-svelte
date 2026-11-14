<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0d8nnbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0d8nnbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:comment-remove-02" {...props}></Icon>
