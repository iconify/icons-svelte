<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-9yltdgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-9yltdgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:music-note-expressive" {...props}></Icon>
