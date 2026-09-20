<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpu4v5b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpu4v5b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:bandrautomation" {...props}></Icon>
