<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pay8v6kzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pay8v6kzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:parasol" {...props}></Icon>
