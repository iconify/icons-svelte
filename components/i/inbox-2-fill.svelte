<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmk3y5beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmk3y5beo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inbox-2-fill" {...props}></Icon>
