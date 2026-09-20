<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-fh_2bfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-fh_2bfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:bookmark" {...props}></Icon>
