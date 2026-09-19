<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_q3dvbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h_q3dvbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:linkedin-v2-fill" {...props}></Icon>
