<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0yme2l2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0yme2l2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kubuntu" {...props}></Icon>
