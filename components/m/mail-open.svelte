<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az9_e8bky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az9_e8bky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mail-open" {...props}></Icon>
