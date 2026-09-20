<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d55gj8bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d55gj8bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cog-solid" {...props}></Icon>
