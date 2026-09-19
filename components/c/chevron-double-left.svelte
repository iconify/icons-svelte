<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7wx2ab2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7wx2ab2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:chevron-double-left" {...props}></Icon>
