<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abl16db3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="abl16db3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:comment-fill" {...props}></Icon>
