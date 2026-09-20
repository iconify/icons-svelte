<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj-_6jdwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aj-_6jdwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cursor-square-bold" {...props}></Icon>
