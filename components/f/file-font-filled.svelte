<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9-u7do2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="j9-u7do2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-font-filled" {...props}></Icon>
