<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z75v8o7wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z75v8o7wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:disability-ad" {...props}></Icon>
