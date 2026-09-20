<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb5tppb5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb5tppb5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:battery-empty" {...props}></Icon>
