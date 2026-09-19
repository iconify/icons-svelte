<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf2xrif2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qf2xrif2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-arrow-left" {...props}></Icon>
