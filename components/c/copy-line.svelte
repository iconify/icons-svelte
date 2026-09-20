<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbq546ify.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbq546ify"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:copy-line" {...props}></Icon>
