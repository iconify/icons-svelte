<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkzro1tab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bkzro1tab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:diploma" {...props}></Icon>
