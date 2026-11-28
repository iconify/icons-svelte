<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti6n5kb0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti6n5kb0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-arrow-down" {...props}></Icon>
