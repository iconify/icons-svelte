<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j18uz8w9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j18uz8w9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:donate-blood" {...props}></Icon>
