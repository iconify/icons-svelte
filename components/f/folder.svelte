<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kow-3lbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kow-3lbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:folder" {...props}></Icon>
