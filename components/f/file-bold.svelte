<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6utdgbib.css';
import '../../css/r/rhj7tk-5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6utdgbib"/><path class="rhj7tk-5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-bold" {...props}></Icon>
