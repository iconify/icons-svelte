<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pw4kkbc-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="pw4kkbc-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:fast-backward-circle" {...props}></Icon>
