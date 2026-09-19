<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaiu7u7ew.css';
import '../../css/l/lh649k1wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gaiu7u7ew"/><path class="lh649k1wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:phone-in-outline" {...props}></Icon>
