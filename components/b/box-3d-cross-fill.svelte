<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmeeo747i.css';
import '../../css/b/bzqhk4t2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmeeo747i"/><path class="bzqhk4t2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-3d-cross-fill" {...props}></Icon>
