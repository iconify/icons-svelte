<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6f0o2r0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6f0o2r0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:align-box-center-top" {...props}></Icon>
