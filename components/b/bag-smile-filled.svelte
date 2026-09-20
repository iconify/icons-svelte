<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8gtrv0ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a8gtrv0ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bag-smile-filled" {...props}></Icon>
