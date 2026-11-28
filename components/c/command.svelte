<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eymtu8xpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eymtu8xpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:command" {...props}></Icon>
