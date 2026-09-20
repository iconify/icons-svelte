<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxn9okbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bxn9okbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:body-outline" {...props}></Icon>
