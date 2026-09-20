<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt_d2pbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt_d2pbbt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:backtop" {...props}></Icon>
