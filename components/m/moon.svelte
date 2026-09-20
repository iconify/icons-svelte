<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/spds58vva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="spds58vva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:moon" {...props}></Icon>
