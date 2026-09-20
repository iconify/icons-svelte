<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1sgz3j6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y1sgz3j6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:eden" {...props}></Icon>
