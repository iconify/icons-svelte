<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht6g7kb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ht6g7kb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:inbox-out-alt" {...props}></Icon>
