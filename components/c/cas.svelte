<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkox7q6wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rkox7q6wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cas" {...props}></Icon>
