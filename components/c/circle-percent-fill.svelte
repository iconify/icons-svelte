<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9seuyb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j9seuyb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-percent-fill" {...props}></Icon>
