<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md39-n46g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md39-n46g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-3-sharp-fill" {...props}></Icon>
