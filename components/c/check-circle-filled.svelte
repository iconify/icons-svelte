<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzv9idc7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tzv9idc7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:check-circle-filled" {...props}></Icon>
