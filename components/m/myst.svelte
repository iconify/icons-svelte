<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3q4rsb-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3q4rsb-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:myst" {...props}></Icon>
