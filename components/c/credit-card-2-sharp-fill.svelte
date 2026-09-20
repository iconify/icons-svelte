<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x188g-mka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x188g-mka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card-2-sharp-fill" {...props}></Icon>
