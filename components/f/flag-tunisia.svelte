<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8cxt48ie.css';
import '../../css/u/ud3dsh8zy.css';
import '../../css/g/g-4znmb1j.css';
import '../../css/z/z6fs5vb8t.css';
import '../../css/q/qy525jbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="e8cxt48ie"/><circle class="ud3dsh8zy"/><path class="g-4znmb1j"/><path class="z6fs5vb8t"/><path class="qy525jbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:flag-tunisia" {...props}></Icon>
