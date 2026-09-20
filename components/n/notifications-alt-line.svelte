<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-m6x_4pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-m6x_4pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:notifications-alt-line" {...props}></Icon>
