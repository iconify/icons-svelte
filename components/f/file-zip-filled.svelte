<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7kkb9bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7kkb9bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-zip-filled" {...props}></Icon>
