<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3nnwrlto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3nnwrlto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:document-text" {...props}></Icon>
