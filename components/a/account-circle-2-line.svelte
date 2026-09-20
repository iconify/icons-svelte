<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft6fc1ajc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft6fc1ajc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:account-circle-2-line" {...props}></Icon>
