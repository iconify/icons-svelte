<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug4jnhcxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ug4jnhcxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-forward-circle-outline" {...props}></Icon>
