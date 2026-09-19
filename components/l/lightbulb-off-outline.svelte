<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4kwtb3sj.css';
import '../../css/l/lw-tv69tr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o4kwtb3sj"/><path clip-rule="evenodd" class="lw-tv69tr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:lightbulb-off-outline" {...props}></Icon>
