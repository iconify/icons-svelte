<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw3ztwb7z.css';
import '../../css/w/wnni9vb7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw3ztwb7z"/><path class="wnni9vb7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:id" {...props}></Icon>
