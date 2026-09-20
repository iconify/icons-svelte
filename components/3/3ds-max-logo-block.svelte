<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abvwlk7nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abvwlk7nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:3ds-max-logo-block" {...props}></Icon>
