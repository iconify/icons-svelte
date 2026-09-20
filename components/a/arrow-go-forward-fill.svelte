<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2bkk_b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2bkk_b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-go-forward-fill" {...props}></Icon>
