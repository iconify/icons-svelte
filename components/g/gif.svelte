<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqbrp3biu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jqbrp3biu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:gif" {...props}></Icon>
