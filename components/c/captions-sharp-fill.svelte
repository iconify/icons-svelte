<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvknj4vry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yvknj4vry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:captions-sharp-fill" {...props}></Icon>
