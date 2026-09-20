<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnx5z5buf.css';
import '../../css/q/qhqeaxbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnx5z5buf"/><path class="qhqeaxbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:box-3d-plus-fill" {...props}></Icon>
