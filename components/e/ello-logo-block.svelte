<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvf_d7bka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xvf_d7bka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:ello-logo-block" {...props}></Icon>
