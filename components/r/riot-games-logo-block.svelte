<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jifvyccms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jifvyccms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:riot-games-logo-block" {...props}></Icon>
