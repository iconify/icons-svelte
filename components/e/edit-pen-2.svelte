<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqb3ih61m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xqb3ih61m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:edit-pen-2" {...props}></Icon>
