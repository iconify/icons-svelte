<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbj8p3c7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qbj8p3c7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-check" {...props}></Icon>
