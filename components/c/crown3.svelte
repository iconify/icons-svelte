<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko02o0b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ko02o0b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:crown3" {...props}></Icon>
