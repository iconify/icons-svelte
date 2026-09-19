<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nopt0ba4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nopt0ba4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-up-right-02" {...props}></Icon>
