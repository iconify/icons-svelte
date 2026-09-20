<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njgul7b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njgul7b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:redo" {...props}></Icon>
