<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j125o4bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j125o4bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:petflap-open" {...props}></Icon>
