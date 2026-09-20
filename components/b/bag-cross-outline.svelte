<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzeji_q_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fzeji_q_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-cross-outline" {...props}></Icon>
