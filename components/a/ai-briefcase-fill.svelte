<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujvt1kxzr.css';
import '../../css/o/oz51gzb3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ujvt1kxzr"/><path clip-rule="evenodd" class="oz51gzb3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-briefcase-fill" {...props}></Icon>
