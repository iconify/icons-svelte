<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-n22ftkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-n22ftkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bold-fill-round" {...props}></Icon>
