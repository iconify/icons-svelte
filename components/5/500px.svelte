<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t541ctb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t541ctb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:500px" {...props}></Icon>
