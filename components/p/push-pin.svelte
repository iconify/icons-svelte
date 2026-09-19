<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y07zuubod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y07zuubod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:push-pin" {...props}></Icon>
