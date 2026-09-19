<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2wo5_mds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2wo5_mds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-long-right" {...props}></Icon>
