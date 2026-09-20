<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbmlh9n1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mbmlh9n1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:glasses-solid-expressive" {...props}></Icon>
