<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eae-4-bqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eae-4-bqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:note-multiple" {...props}></Icon>
