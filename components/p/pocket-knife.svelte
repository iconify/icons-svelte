<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufavf3byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufavf3byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:pocket-knife" {...props}></Icon>
