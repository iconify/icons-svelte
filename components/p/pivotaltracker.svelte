<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6grndb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6grndb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pivotaltracker" {...props}></Icon>
