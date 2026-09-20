<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv09q5bgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv09q5bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:airserbia" {...props}></Icon>
