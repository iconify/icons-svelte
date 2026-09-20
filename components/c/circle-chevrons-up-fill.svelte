<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx70z0b6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fx70z0b6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-chevrons-up-fill" {...props}></Icon>
