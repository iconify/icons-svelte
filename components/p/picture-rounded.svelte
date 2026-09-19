<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2o2k5bfa.css';
import '../../css/e/eafmg15uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="e2o2k5bfa"/><path class="eafmg15uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:picture-rounded" {...props}></Icon>
