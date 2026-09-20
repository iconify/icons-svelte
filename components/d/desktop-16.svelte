<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekuwo8vtc.css';
import '../../css/a/a5pezv9ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ekuwo8vtc"/><path clip-rule="evenodd" class="a5pezv9ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:desktop-16" {...props}></Icon>
