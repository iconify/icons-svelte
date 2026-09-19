<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn_vi9bnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sn_vi9bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:chevrons-collapse-vertical-to-line" {...props}></Icon>
