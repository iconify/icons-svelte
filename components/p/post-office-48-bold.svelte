<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjpjj7bux.css';
import '../../css/f/fa8ycbb8q.css';
import '../../css/e/epesvsbmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bjpjj7bux"/><path class="fa8ycbb8q"/><path class="epesvsbmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:post-office-48-bold" {...props}></Icon>
