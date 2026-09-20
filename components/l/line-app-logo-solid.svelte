<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7ho8gb3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q7ho8gb3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:line-app-logo-solid" {...props}></Icon>
