<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o86-0b4qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="o86-0b4qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:discover" {...props}></Icon>
