<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4zbgebyk.css';
import '../../css/b/bb6-y3inu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4zbgebyk"/><path class="bb6-y3inu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-md" {...props}></Icon>
