<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akhwoit6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":660,"height":717};
const content = `<path class="akhwoit6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:off" {...props}></Icon>
