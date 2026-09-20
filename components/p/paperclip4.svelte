<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kqov67dag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kqov67dag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:paperclip4" {...props}></Icon>
