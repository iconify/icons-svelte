<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0llrhkep.css';
import '../../css/p/pbyqebu6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b0llrhkep"/><path class="pbyqebu6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:photo-camera-crossed-32" {...props}></Icon>
