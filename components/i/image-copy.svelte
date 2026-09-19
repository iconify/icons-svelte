<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln-l7001b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ln-l7001b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:image-copy" {...props}></Icon>
