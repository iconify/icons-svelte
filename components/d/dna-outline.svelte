<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okjza0b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="okjza0b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dna-outline" {...props}></Icon>
