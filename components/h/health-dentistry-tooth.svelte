<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxqhxbc1l.css';
import '../../css/f/fo7gk3lhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gxqhxbc1l"/><path class="fo7gk3lhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-dentistry-tooth" {...props}></Icon>
