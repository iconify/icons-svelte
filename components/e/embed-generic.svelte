<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea-ejob2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ea-ejob2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:embed-generic" {...props}></Icon>
