<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o291p-a2z.css';
import '../../css/c/cd4vo0b5j.css';
import '../../css/l/lho28-27t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="o291p-a2z"/><path class="cd4vo0b5j"/><path class="lho28-27t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:folder-minus" {...props}></Icon>
