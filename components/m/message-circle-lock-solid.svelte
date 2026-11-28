<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjzzi15jw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jjzzi15jw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:message-circle-lock-solid" {...props}></Icon>
