<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp03_1bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-7,"top":-7};
const content = `<path class="kp03_1bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-up-right" {...props}></Icon>
