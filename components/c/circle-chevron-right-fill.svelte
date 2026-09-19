<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6cmpy5to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t6cmpy5to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-chevron-right-fill" {...props}></Icon>
