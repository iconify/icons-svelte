<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6cij9bpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6cij9bpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-plus-fill-round" {...props}></Icon>
