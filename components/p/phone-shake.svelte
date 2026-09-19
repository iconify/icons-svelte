<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh-ab2_gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh-ab2_gu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:phone-shake" {...props}></Icon>
