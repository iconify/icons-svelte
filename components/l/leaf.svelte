<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kquklebln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kquklebln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:leaf" {...props}></Icon>
