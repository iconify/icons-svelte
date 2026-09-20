<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjj1ddcwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjj1ddcwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:elixir-logo-block" {...props}></Icon>
