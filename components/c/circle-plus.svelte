<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgcbpcb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vgcbpcb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-plus" {...props}></Icon>
