<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp6o6d8oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fp6o6d8oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:oculus-logo-solid" {...props}></Icon>
