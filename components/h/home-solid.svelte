<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro-ic_bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro-ic_bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:home-solid" {...props}></Icon>
