<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn_jll_0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hn_jll_0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:fast-backward" {...props}></Icon>
