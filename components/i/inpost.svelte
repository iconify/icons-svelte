<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm29j4bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bm29j4bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:inpost" {...props}></Icon>
