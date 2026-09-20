<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-jq0l3km.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r-jq0l3km"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:rbxmk" {...props}></Icon>
