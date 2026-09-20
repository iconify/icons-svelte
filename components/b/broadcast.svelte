<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umylk03ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="umylk03ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:broadcast" {...props}></Icon>
