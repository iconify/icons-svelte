<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9dpl7yvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e9dpl7yvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bebo-logo-solid" {...props}></Icon>
