<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcpwybcwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kcpwybcwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bus-2-fill" {...props}></Icon>
