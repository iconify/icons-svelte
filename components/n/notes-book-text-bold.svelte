<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxhblib2y.css';
import '../../css/e/e92p4ac2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxhblib2y"/><path class="e92p4ac2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:notes-book-text-bold" {...props}></Icon>
