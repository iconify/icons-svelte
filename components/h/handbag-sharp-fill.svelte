<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq-vnebps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fq-vnebps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:handbag-sharp-fill" {...props}></Icon>
