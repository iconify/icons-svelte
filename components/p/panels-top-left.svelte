<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmgkxl6jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmgkxl6jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:panels-top-left" {...props}></Icon>
