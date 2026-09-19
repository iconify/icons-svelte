<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3f61bbyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q3f61bbyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pencil" {...props}></Icon>
