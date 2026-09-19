<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sozr8sbps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sozr8sbps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:dna-24px" {...props}></Icon>
