<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8tn4t_cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="b8tn4t_cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:discord-alt" {...props}></Icon>
