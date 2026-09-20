<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3f8h8t0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x3f8h8t0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:hierarchy-line-1-flat" {...props}></Icon>
