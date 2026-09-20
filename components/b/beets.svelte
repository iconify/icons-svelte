<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqw0fe5oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aqw0fe5oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:beets" {...props}></Icon>
