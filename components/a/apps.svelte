<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2nposhfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2nposhfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:apps" {...props}></Icon>
