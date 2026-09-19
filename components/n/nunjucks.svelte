<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu5o7c14i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tu5o7c14i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:nunjucks" {...props}></Icon>
