<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhj7tk-5q.css';
import '../../css/q/qgg_romwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rhj7tk-5q"/><path clip-rule="evenodd" class="qgg_romwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-file-bold" {...props}></Icon>
