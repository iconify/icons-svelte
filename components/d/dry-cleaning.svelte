<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fys4zfbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fys4zfbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ginetex:dry-cleaning" {...props}></Icon>
