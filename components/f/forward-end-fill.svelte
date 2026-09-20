<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kja92kcsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kja92kcsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:forward-end-fill" {...props}></Icon>
