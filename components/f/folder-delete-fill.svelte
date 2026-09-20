<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkzn81bqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkzn81bqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-delete-fill" {...props}></Icon>
