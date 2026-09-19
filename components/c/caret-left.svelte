<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa9bxsb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="oa9bxsb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:caret-left" {...props}></Icon>
