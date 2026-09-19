<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttjhx24hk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ttjhx24hk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:crop" {...props}></Icon>
