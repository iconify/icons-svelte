<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qnaerzb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qnaerzb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:protonmail-logo-2-solid" {...props}></Icon>
