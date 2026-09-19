<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sha7p4r6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sha7p4r6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:rewind-left-fill" {...props}></Icon>
