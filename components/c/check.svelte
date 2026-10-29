<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id-kspbgm.css';
import '../../css/f/f-y-gabit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id-kspbgm"/><path class="f-y-gabit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:check" {...props}></Icon>
