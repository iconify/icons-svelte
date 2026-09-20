<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7a9p93tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7a9p93tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chevron-right-24" {...props}></Icon>
