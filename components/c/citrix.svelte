<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9l-hbbsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a9l-hbbsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:citrix" {...props}></Icon>
