<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atgd69b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="atgd69b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:menu-endways-outline" {...props}></Icon>
