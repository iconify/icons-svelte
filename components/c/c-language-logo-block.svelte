<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/up54fzbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="up54fzbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:c-language-logo-block" {...props}></Icon>
