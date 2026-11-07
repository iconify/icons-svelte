<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/newyx7bgu.css';
import '../../css/l/lzldlfb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="newyx7bgu"/><path class="lzldlfb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:podcast-bold-duotone" {...props}></Icon>
