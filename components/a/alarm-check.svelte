<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh0qlyhsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hh0qlyhsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:alarm-check" {...props}></Icon>
