<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcf13zcuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcf13zcuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:judaism" {...props}></Icon>
