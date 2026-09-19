<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lub4f059b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lub4f059b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:code-pull-request-xmark" {...props}></Icon>
