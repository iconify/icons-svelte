<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b33p915kt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b33p915kt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kik-logo-2-block" {...props}></Icon>
