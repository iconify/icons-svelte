<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7xw74zlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7xw74zlj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:headphone-slash" {...props}></Icon>
