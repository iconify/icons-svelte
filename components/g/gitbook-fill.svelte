<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf__stwih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf__stwih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:gitbook-fill" {...props}></Icon>
