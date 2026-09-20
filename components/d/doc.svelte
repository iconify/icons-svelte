<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oiyw48fhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oiyw48fhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:doc" {...props}></Icon>
