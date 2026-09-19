<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx-jz0bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vx-jz0bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:database" {...props}></Icon>
