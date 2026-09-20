<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyz__6bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nyz__6bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:hashtag-outline" {...props}></Icon>
