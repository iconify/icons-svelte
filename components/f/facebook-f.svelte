<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afrs0sbhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afrs0sbhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:facebook-f" {...props}></Icon>
