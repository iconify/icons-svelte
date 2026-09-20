<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5jvu2jmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q5jvu2jmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lydia" {...props}></Icon>
