<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9q3ovbku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r9q3ovbku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:paintbucket-outline" {...props}></Icon>
