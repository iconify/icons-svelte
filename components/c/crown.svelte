<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az7xd_bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-4};
const content = `<path class="az7xd_bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:crown" {...props}></Icon>
