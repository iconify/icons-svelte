<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fujslo8xa.css';
import '../../css/h/hchurepih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fujslo8xa"/><path class="hchurepih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:badge-dollar-light" {...props}></Icon>
