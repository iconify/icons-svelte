<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw4mo75jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aw4mo75jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:gowalla-logo-4-block" {...props}></Icon>
