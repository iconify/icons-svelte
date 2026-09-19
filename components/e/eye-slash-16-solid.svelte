<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwooq4bpl.css';
import '../../css/z/zkjh13stl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nwooq4bpl"/><path class="zkjh13stl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:eye-slash-16-solid" {...props}></Icon>
