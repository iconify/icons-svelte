<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3eoodb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l3eoodb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-up-outline" {...props}></Icon>
