<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1841vb1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h1841vb1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kick-logo-logo-block" {...props}></Icon>
