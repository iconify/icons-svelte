<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozgt7tt7d.css';
import '../../css/r/rhx5tab9t.css';
import '../../css/l/l49vyab9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ozgt7tt7d"/><path class="rhx5tab9t"/><path clip-rule="evenodd" class="l49vyab9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:jar-of-pills-2-outline" {...props}></Icon>
