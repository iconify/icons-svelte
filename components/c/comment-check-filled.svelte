<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai4s28y9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ai4s28y9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:comment-check-filled" {...props}></Icon>
