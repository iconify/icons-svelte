<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/juikwj71p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="juikwj71p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:eclipse-ide-logo-block" {...props}></Icon>
