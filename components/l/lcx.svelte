<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucp5eibww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ucp5eibww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:lcx" {...props}></Icon>
