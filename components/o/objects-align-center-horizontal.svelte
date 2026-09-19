<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocsj0ygwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ocsj0ygwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:objects-align-center-horizontal" {...props}></Icon>
