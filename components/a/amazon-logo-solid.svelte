<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-kb-fhla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-kb-fhla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:amazon-logo-solid" {...props}></Icon>
