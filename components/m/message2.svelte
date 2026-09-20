<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n01jmhb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n01jmhb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:message2" {...props}></Icon>
