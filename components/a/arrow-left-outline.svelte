<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmgz4fbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmgz4fbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:arrow-left-outline" {...props}></Icon>
