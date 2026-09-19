<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-ddl3baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a-ddl3baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cloud-arrow-down-16-solid" {...props}></Icon>
