<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roww8j_pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="roww8j_pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:patreon-logo-solid" {...props}></Icon>
