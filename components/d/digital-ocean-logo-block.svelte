<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j52dsfb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j52dsfb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:digital-ocean-logo-block" {...props}></Icon>
