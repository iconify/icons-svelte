<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_lhvpb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="u_lhvpb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:grooveshark" {...props}></Icon>
