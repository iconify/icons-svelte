<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkmv4-31v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hkmv4-31v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:betalist-logo-block" {...props}></Icon>
