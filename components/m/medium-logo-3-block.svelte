<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dihbw3u5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dihbw3u5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:medium-logo-3-block" {...props}></Icon>
