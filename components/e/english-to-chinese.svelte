<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igsh0jz_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igsh0jz_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:english-to-chinese" {...props}></Icon>
