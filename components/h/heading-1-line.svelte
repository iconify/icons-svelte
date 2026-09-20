<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcxvpxqpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcxvpxqpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heading-1-line" {...props}></Icon>
