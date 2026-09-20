<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf_jk485b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf_jk485b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:box" {...props}></Icon>
