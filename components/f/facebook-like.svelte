<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc63pd39v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc63pd39v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:facebook-like" {...props}></Icon>
