<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk7uxg33b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tk7uxg33b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bed-double-sharp" {...props}></Icon>
