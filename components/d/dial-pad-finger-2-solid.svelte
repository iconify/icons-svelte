<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw4tq_q9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hw4tq_q9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:dial-pad-finger-2-solid" {...props}></Icon>
