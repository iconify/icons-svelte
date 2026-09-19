<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/loqafrfoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="loqafrfoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:book-mark-outline" {...props}></Icon>
