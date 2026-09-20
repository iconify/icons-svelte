<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5kwrbb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l5kwrbb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:brush-outline" {...props}></Icon>
