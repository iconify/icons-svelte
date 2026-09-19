<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yymv9fyfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yymv9fyfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:folder-plus" {...props}></Icon>
