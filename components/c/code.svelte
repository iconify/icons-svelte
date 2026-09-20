<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-9g3kbjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-9g3kbjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:code" {...props}></Icon>
