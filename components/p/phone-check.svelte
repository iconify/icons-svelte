<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zeh_gubsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zeh_gubsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:phone-check" {...props}></Icon>
