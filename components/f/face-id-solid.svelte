<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6tjm_bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="u6tjm_bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:face-id-solid" {...props}></Icon>
