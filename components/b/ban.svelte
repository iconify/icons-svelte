<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai7aleert.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ai7aleert"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:ban" {...props}></Icon>
