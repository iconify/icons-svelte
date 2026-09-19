<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8s03dbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p8s03dbpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-chevron-left-fill" {...props}></Icon>
