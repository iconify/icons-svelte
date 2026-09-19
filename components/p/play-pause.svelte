<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lusqrr91b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lusqrr91b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:play-pause" {...props}></Icon>
