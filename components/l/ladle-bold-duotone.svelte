<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo5hu07_i.css';
import '../../css/s/s7zqjx21v.css';
import '../../css/n/nyn8xjb3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo5hu07_i"/><path class="s7zqjx21v"/><path class="nyn8xjb3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ladle-bold-duotone" {...props}></Icon>
