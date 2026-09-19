<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pefrpe-di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pefrpe-di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:gem" {...props}></Icon>
