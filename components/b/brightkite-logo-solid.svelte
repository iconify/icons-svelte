<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trqcy87qc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="trqcy87qc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:brightkite-logo-solid" {...props}></Icon>
