<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf64je3mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf64je3mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:mark-github-24" {...props}></Icon>
