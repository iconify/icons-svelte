<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak_u2fnec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ak_u2fnec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:moon-16" {...props}></Icon>
