<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk1kz6c0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk1kz6c0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:message-square-x-fill" {...props}></Icon>
