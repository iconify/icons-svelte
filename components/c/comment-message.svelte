<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaz6k6b-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qaz6k6b-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-message" {...props}></Icon>
