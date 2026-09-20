<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or80zd0ep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="or80zd0ep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:camera-add2-filled" {...props}></Icon>
