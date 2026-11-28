<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxr_mew3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary xxr_mew3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:heptagon-duotone" {...props}></Icon>
