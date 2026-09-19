<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zml5j5fup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zml5j5fup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:database-plus" {...props}></Icon>
