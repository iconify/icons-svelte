<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lm_90bcmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm_90bcmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mealie" {...props}></Icon>
