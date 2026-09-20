<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acnfg6bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acnfg6bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bow-filled" {...props}></Icon>
