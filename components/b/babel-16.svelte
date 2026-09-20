<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h40kk1bvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="h40kk1bvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:babel-16" {...props}></Icon>
