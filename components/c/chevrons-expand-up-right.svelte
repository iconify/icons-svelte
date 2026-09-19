<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jctdkdj8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jctdkdj8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:chevrons-expand-up-right" {...props}></Icon>
