<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buugc9b2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="buugc9b2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:objects-align-center-vertical" {...props}></Icon>
