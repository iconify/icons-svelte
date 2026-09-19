<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2i58labe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w2i58labe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:object-align-center-horizontal" {...props}></Icon>
