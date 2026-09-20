<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z90tcxiee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="z90tcxiee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:edit-alt-5" {...props}></Icon>
