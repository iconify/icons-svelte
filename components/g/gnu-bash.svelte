<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehqum42-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ehqum42-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:gnu-bash" {...props}></Icon>
