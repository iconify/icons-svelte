<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4v8ixnew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4v8ixnew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:rocky-linux" {...props}></Icon>
