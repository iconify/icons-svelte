<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoxpwbb0y.css';
import '../../css/b/b1-hh0bot.css';
import '../../css/s/s2otf6w0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoxpwbb0y"/><path clip-rule="evenodd" class="b1-hh0bot"/><path class="s2otf6w0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:credit-card-plus-filled" {...props}></Icon>
