<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9h01f9wo.css';
import '../../css/b/b5ybc4bew.css';
import '../../css/b/bvct38blc.css';
import '../../css/a/abgizhdkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9h01f9wo"/><path class="b5ybc4bew"/><path class="bvct38blc"/><path class="abgizhdkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:grid-2x2-add-bold" {...props}></Icon>
