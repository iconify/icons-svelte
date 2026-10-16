<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5_6-abcl.css';
import '../../css/o/of1wzvb1f.css';
import '../../css/o/oef6x1_vi.css';
import '../../css/e/ekxhm6afd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y5_6-abcl"/><path class="of1wzvb1f"/><path class="oef6x1_vi"/><path class="ekxhm6afd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:photodiode-48" {...props}></Icon>
