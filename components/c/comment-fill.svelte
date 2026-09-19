<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtb49rb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xtb49rb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:comment-fill" {...props}></Icon>
