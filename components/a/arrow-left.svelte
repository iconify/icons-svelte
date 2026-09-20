<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sich1rccl.css';
import '../../css/p/p4luhxbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sich1rccl"/><path class="p4luhxbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:arrow-left" {...props}></Icon>
