<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmjyao5le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qmjyao5le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:documents-outline" {...props}></Icon>
