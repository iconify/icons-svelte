<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvp031i9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvp031i9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:corner-left-down" {...props}></Icon>
