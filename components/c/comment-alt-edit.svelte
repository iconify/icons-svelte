<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6a_jrb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g6a_jrb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt-edit" {...props}></Icon>
