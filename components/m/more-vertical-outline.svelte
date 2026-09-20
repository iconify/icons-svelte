<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwapf4b9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uwapf4b9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:more-vertical-outline" {...props}></Icon>
