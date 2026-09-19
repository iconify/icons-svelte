<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/syy6vlbtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":486.037,"height":1000};
const content = `<path class="syy6vlbtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="brandico:facebook" {...props}></Icon>
