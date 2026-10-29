<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljqxp7vec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljqxp7vec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:play" {...props}></Icon>
