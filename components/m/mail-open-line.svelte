<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfq6du_me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfq6du_me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mail-open-line" {...props}></Icon>
