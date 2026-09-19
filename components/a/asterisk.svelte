<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_ljy9dwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_ljy9dwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:asterisk" {...props}></Icon>
