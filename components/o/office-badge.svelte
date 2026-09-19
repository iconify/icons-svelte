<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px1aoe-8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="px1aoe-8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:office-badge" {...props}></Icon>
