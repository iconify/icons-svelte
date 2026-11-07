<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mo43we00a.css';
import '../../css/f/f521zmbvd.css';
import '../../css/u/u30xcbbdf.css';
import '../../css/c/c4946-17v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mo43we00a"/><path class="f521zmbvd"/><path class="u30xcbbdf"/><path class="c4946-17v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-text-bold-duotone" {...props}></Icon>
