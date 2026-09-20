<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfzlipmmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfzlipmmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lock-open-keyhole" {...props}></Icon>
