<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soqjl9b2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="soqjl9b2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:nuke-logo-block" {...props}></Icon>
