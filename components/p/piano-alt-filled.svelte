<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fddobqp8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fddobqp8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:piano-alt-filled" {...props}></Icon>
