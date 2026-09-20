<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntluh2bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntluh2bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-b-small" {...props}></Icon>
