<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nll8v2b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nll8v2b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:repeat-one-line" {...props}></Icon>
