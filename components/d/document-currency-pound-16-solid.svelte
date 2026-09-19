<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpsi-dbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bpsi-dbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:document-currency-pound-16-solid" {...props}></Icon>
