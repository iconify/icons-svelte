<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi8hw16yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wi8hw16yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:north-west-square-fill" {...props}></Icon>
