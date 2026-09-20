<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxyw8z7ql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hxyw8z7ql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:inbox-out" {...props}></Icon>
