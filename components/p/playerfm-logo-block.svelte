<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxiq8gbgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jxiq8gbgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:playerfm-logo-block" {...props}></Icon>
