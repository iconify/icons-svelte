<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckcehewfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckcehewfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:bookmark" {...props}></Icon>
