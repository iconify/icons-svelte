<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nblah3f0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nblah3f0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:more-02" {...props}></Icon>
