<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgj3g-brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bgj3g-brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:home-smile2-filled" {...props}></Icon>
