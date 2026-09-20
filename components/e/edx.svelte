<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntd2lyfxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntd2lyfxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:edx" {...props}></Icon>
