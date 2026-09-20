<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5ef9db-k.css';
import '../../css/o/odnck4blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j5ef9db-k"/><path class="odnck4blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:generate-content" {...props}></Icon>
