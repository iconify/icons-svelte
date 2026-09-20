<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljk3adyvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ljk3adyvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:mug" {...props}></Icon>
