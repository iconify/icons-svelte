<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axoztvb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axoztvb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:more-horizontal" {...props}></Icon>
