<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iu6ae2f3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iu6ae2f3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:apple-outline" {...props}></Icon>
