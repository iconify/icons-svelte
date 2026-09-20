<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c38vhob8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c38vhob8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:folder-fill" {...props}></Icon>
