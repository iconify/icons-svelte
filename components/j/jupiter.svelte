<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2j8v3hlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2j8v3hlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:jupiter" {...props}></Icon>
