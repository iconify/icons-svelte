<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk2kl50ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk2kl50ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:knowledge-01" {...props}></Icon>
