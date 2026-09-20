<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj67z3bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pj67z3bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:drag-squares-vertical-light" {...props}></Icon>
