<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo0or-nle.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bo0or-nle"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:image-sharp-fill" {...props}></Icon>
