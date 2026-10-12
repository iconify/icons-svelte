<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbwwvpusx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tbwwvpusx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-box-up-20" {...props}></Icon>
