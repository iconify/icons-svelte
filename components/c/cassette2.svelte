<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z5-e6wbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z5-e6wbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cassette2" {...props}></Icon>
