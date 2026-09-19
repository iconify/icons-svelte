<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xum33lbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xum33lbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:do-undo-bold" {...props}></Icon>
