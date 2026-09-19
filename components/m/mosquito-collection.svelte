<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3jxn1xds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="u3jxn1xds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mosquito-collection" {...props}></Icon>
