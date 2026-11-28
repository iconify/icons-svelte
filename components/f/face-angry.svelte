<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6r1e5d7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6r1e5d7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:face-angry" {...props}></Icon>
