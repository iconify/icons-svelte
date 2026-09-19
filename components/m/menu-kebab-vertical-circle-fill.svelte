<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxxn7yb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxxn7yb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-kebab-vertical-circle-fill" {...props}></Icon>
