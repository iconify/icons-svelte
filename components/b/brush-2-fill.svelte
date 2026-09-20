<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj_jlubrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj_jlubrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brush-2-fill" {...props}></Icon>
