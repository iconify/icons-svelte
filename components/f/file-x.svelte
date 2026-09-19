<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj3cfcodp.css';
import '../../css/z/z132mnbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rj3cfcodp"/><path class="z132mnbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-x" {...props}></Icon>
