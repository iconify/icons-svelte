<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9qks5bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9qks5bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:messages-square-fill" {...props}></Icon>
