<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xomsf6buj.css';
import '../../css/o/o7jf5lv9i.css';
import '../../css/j/jtfx71bvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xomsf6buj"/><path clip-rule="evenodd" class="o7jf5lv9i"/><path class="jtfx71bvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:credit-card-x-filled" {...props}></Icon>
