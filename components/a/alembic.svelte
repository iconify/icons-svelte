<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-3igr9gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m-3igr9gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:alembic" {...props}></Icon>
