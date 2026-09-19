<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxai6ezyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxai6ezyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:check-plus-circle-outline" {...props}></Icon>
