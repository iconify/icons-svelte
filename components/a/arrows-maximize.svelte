<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blb603pzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="blb603pzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrows-maximize" {...props}></Icon>
