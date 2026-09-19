<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mi6i5jb0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="mi6i5jb0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:baby-male-0306m2x-outline" {...props}></Icon>
