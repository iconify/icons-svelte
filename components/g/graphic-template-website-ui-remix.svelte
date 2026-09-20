<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxu6bcb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pxu6bcb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:graphic-template-website-ui-remix" {...props}></Icon>
