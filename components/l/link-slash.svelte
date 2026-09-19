<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwx_n2boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pwx_n2boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:link-slash" {...props}></Icon>
