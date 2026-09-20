<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1nc17b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1nc17b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:flow-branch-line" {...props}></Icon>
