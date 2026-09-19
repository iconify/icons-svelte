<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfa--6bnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfa--6bnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:mail" {...props}></Icon>
