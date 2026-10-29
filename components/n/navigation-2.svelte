<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2swq-gzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2swq-gzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:navigation-2" {...props}></Icon>
