<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gbk1xnc1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gbk1xnc1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:automobile-small" {...props}></Icon>
