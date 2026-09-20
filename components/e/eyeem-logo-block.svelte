<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyk52k0bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eyk52k0bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:eyeem-logo-block" {...props}></Icon>
