<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akc8dfwwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akc8dfwwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:adjust-brightness" {...props}></Icon>
