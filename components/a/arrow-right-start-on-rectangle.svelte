<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqpb84glt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gqpb84glt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-right-start-on-rectangle" {...props}></Icon>
