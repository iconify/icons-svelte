<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp66c-b3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp66c-b3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:arrow-alt-lright-alt" {...props}></Icon>
