<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab4osybgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ab4osybgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bowknot-fill" {...props}></Icon>
