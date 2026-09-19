<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnh_m9b1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="pnh_m9b1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:folder-open-fill" {...props}></Icon>
