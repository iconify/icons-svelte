<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9lsjlp9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n9lsjlp9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:elevator" {...props}></Icon>
