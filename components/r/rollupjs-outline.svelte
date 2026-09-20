<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt6rq6zsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mt6rq6zsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:rollupjs-outline" {...props}></Icon>
