<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwf-mbcfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwf-mbcfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:bolt-alt" {...props}></Icon>
