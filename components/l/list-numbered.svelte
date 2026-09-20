<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alpe4e-yq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="alpe4e-yq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:list-numbered" {...props}></Icon>
