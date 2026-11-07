<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1g98hbyj.css';
import '../../css/r/rhj7tk-5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r1g98hbyj"/><path class="rhj7tk-5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-text-bold" {...props}></Icon>
