<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h27hywb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h27hywb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:maya-logo-block" {...props}></Icon>
