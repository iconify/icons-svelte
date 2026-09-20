<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0v2wcciq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b0v2wcciq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kai-os-logo-block" {...props}></Icon>
