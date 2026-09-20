<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw5w5orfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jw5w5orfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:ellipsis-circle-solid-expressive" {...props}></Icon>
