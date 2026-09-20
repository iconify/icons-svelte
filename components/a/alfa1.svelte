<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym2f5wksi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ym2f5wksi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:alfa1" {...props}></Icon>
