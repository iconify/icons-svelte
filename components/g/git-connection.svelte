<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp6pvjrvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hp6pvjrvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-connection" {...props}></Icon>
