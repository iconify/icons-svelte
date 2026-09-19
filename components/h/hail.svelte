<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d09-d0b7r.css';
import '../../css/f/f9l077jci.css';
import '../../css/l/lxgy755lv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d09-d0b7r"/><path class="f9l077jci"/><path class="lxgy755lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hail" {...props}></Icon>
