<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b05fhublq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b05fhublq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:package-off" {...props}></Icon>
