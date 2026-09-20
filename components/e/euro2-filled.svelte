<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuww5n5ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuww5n5ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:euro2-filled" {...props}></Icon>
