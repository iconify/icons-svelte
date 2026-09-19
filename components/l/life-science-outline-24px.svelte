<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1m8crbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u1m8crbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:life-science-outline-24px" {...props}></Icon>
