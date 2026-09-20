<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypalqe4ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ypalqe4ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home-wifi3-filled" {...props}></Icon>
