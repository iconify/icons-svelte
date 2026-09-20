<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg5puvrns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hg5puvrns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:f-droid-logo-block" {...props}></Icon>
