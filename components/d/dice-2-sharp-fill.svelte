<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciwk1uokv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ciwk1uokv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-2-sharp-fill" {...props}></Icon>
