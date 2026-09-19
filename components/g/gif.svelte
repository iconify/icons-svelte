<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i58x1vbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i58x1vbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:gif" {...props}></Icon>
