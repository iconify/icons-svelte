<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdzjk4bvt.css';
import '../../css/o/osqzglbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qdzjk4bvt"/><path clip-rule="evenodd" class="osqzglbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:keyboard-16" {...props}></Icon>
