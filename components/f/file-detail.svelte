<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z132mnbgz.css';
import '../../css/g/gcakk6n9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z132mnbgz"/><path class="gcakk6n9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-detail" {...props}></Icon>
