<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m7f6twbnp.css';
import '../../css/s/s5_vv4szb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m7f6twbnp"/><path class="s5_vv4szb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:blur-alt" {...props}></Icon>
