<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b03u49keo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b03u49keo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:globe-plus" {...props}></Icon>
