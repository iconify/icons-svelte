<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp05wnb8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dp05wnb8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:mail" {...props}></Icon>
