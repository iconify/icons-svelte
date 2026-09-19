<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_soudvrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="p_soudvrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:callalt" {...props}></Icon>
