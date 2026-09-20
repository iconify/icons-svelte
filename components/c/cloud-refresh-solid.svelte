<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2o8lkbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s2o8lkbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cloud-refresh-solid" {...props}></Icon>
