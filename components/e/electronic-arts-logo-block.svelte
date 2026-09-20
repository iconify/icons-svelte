<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf5tjob_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xf5tjob_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:electronic-arts-logo-block" {...props}></Icon>
