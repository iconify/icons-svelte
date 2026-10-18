<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mol150b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mol150b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:hand" {...props}></Icon>
