<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_v0_v6mz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_v0_v6mz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:paper-airplane" {...props}></Icon>
