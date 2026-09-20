<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1mk5dhbx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1mk5dhbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:menu-dots-24" {...props}></Icon>
