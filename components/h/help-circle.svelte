<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwp7mzb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwp7mzb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:help-circle" {...props}></Icon>
