<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/titb3kk7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="titb3kk7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:codepen-logo-block" {...props}></Icon>
