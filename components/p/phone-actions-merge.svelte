<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj2ms3n-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rj2ms3n-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:phone-actions-merge" {...props}></Icon>
