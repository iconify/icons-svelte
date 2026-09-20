<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i87ksnb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i87ksnb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:coffee" {...props}></Icon>
