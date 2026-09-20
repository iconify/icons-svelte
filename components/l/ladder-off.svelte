<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eie6a02dw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eie6a02dw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ladder-off" {...props}></Icon>
