<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjbf6hs1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rjbf6hs1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:face-with-open-mouth-fill" {...props}></Icon>
