<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdlbvbcjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fdlbvbcjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-arrow-down-right-fill" {...props}></Icon>
