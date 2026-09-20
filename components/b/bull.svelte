<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kruzd2qkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kruzd2qkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bull" {...props}></Icon>
