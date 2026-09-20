<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdl7h5bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pdl7h5bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-offset-left-sharp-fill" {...props}></Icon>
