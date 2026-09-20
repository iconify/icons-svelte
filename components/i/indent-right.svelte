<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpcrhcb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hpcrhcb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:indent-right" {...props}></Icon>
