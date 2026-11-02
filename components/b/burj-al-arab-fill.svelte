<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qa3y0g5gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qa3y0g5gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:burj-al-arab-fill" {...props}></Icon>
