<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jt8pr1bds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jt8pr1bds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevron-last" {...props}></Icon>
