<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo6jg5d0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo6jg5d0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arlo-q" {...props}></Icon>
