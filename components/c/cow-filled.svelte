<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdr-j5q6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fdr-j5q6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:cow-filled" {...props}></Icon>
