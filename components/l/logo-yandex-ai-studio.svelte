<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3f2ys1ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d3f2ys1ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-yandex-ai-studio" {...props}></Icon>
