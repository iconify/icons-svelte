<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a919obopo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a919obopo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:photo" {...props}></Icon>
