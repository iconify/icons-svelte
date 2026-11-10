<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cagdqbcef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cagdqbcef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:document-x-mark-solid" {...props}></Icon>
