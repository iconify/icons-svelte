<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beqydvjmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="beqydvjmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:adobe-alt" {...props}></Icon>
