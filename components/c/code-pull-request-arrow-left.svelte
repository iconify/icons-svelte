<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7_a9xxqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a7_a9xxqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:code-pull-request-arrow-left" {...props}></Icon>
