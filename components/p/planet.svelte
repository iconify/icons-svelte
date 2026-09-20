<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc5a15b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bc5a15b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:planet" {...props}></Icon>
