<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p21dizb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p21dizb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:backslash" {...props}></Icon>
