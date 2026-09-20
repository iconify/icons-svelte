<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k63r90tuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k63r90tuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:qik-logo-block" {...props}></Icon>
