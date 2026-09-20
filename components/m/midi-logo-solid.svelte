<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-y7qc5fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-y7qc5fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:midi-logo-solid" {...props}></Icon>
