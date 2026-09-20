<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvxwz-brr.css';
import '../../css/z/zpzbcrshu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gvxwz-brr"/><path class="zpzbcrshu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:rope-fence" {...props}></Icon>
