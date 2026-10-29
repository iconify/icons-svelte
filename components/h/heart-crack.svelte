<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw5qyibzg.css';
import '../../css/j/jfyntqbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw5qyibzg"/><path class="jfyntqbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:heart-crack" {...props}></Icon>
