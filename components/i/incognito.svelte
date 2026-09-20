<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mv2a2abyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mv2a2abyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:incognito" {...props}></Icon>
