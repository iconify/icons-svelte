<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef35mebft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ef35mebft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alarm-off" {...props}></Icon>
