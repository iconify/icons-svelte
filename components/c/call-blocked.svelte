<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hghv_cv8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hghv_cv8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-blocked" {...props}></Icon>
