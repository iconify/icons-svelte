<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9h4qu6lx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u9h4qu6lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-f" {...props}></Icon>
